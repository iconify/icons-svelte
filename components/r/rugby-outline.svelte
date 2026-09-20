<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btd8tbbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="btd8tbbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rugby-outline" {...props}></Icon>
