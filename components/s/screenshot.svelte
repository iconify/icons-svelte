<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/o/o7iybpjze.css';
import '../../css/g/gg8oa7bti.css';
import '../../css/h/hrp4v8boa.css';
import '../../css/r/rp4j_8b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="o7iybpjze"/><path class="gg8oa7bti"/><path class="hrp4v8boa"/><path class="rp4j_8b9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:screenshot" {...props}></Icon>
