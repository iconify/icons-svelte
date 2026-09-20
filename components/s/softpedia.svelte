<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcl10mxau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcl10mxau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:softpedia" {...props}></Icon>
