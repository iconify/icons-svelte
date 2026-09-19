<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onyqr8g1f.css';
import '../../css/f/f80vq2bep.css';
import '../../css/i/iiw_n9bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="onyqr8g1f"/><path class="f80vq2bep"/><path class="iiw_n9bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ru-1x1" {...props}></Icon>
