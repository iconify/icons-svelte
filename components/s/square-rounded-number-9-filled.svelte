<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe_qc0b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_qc0b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-9-filled" {...props}></Icon>
