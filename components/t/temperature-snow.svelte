<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/yk-2fob0v.css';
import '../../css/a/acmzzzbif.css';
import '../../css/f/f1_qbxbln.css';
import '../../css/m/mantc1b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yk-2fob0v"/><path class="acmzzzbif"/><path class="f1_qbxbln"/><path class="mantc1b5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:temperature-snow" {...props}></Icon>
