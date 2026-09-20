<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0v10zhqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0v10zhqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sun-outline" {...props}></Icon>
