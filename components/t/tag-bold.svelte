<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-gh-maxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-gh-maxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-bold" {...props}></Icon>
