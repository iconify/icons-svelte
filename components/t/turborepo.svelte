<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjtv-0f9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtv-0f9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:turborepo" {...props}></Icon>
