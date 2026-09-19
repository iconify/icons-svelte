<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1pm3vbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b1pm3vbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:softclipcurve" {...props}></Icon>
