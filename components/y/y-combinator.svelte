<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfn47jbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jfn47jbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:y-combinator" {...props}></Icon>
