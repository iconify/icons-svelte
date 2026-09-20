<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaxt9jb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaxt9jb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:temperature-low" {...props}></Icon>
