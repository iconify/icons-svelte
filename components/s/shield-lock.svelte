<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuxsv2bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuxsv2bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shield-lock" {...props}></Icon>
