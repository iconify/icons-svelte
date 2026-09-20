<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qwm-occyl.css';
import '../../css/m/mg2yxg0pk.css';
import '../../css/n/n4vlayblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qwm-occyl"/><path class="mg2yxg0pk"/><path class="n4vlayblf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:stamps-portrait-1" {...props}></Icon>
