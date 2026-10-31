<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnf5qz6qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnf5qz6qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-gloss" {...props}></Icon>
