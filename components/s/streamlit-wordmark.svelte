<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyp86db-i.css';
import '../../css/h/hrs2k7xqz.css';
import '../../css/v/v7ll8i85l.css';
import '../../css/a/a0xyf1bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zyp86db-i"/><path class="hrs2k7xqz"/><path class="v7ll8i85l"/><path class="a0xyf1bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:streamlit-wordmark" {...props}></Icon>
