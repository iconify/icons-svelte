<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/q/qv35mhr5v.css';
import '../../css/h/ho8lzkf2o.css';
import '../../css/c/cowgu0bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="qv35mhr5v wm-shadow"/><path class="ho8lzkf2o wm-shadow"/><path class="cowgu0bvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:sliders" {...props}></Icon>
