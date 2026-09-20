<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg817wbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg817wbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-square-filled" {...props}></Icon>
