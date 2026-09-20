<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8s6xvu0y.css';
import '../../css/c/cmb2wab2t.css';
import '../../css/g/g00s9kkvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w8s6xvu0y"/><path class="cmb2wab2t"/><path clip-rule="evenodd" class="g00s9kkvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-query-sql" {...props}></Icon>
