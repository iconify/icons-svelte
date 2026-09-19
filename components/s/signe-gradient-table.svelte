<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr_1hu37k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_1hu37k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:signe-gradient-table" {...props}></Icon>
