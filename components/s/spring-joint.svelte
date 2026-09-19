<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja56ooacg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ja56ooacg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:spring-joint" {...props}></Icon>
