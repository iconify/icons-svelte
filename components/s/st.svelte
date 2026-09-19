<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qxlgbccih.css';
import '../../css/k/k_pdj69rf.css';
import '../../css/u/ui2s02ojw.css';
import '../../css/h/hadzi1b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qxlgbccih"/><path class="k_pdj69rf"/><path class="ui2s02ojw"/><path class="hadzi1b-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:st" {...props}></Icon>
