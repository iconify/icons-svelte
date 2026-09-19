<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/v/vi1e7rb5q.css';
import '../../css/l/lncnfvbwz.css';
import '../../css/g/glfhpzbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="flen3tbdj"><circle class="vi1e7rb5q"/><circle class="lncnfvbwz"/><path class="glfhpzbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:voicemail-fill-16" {...props}></Icon>
