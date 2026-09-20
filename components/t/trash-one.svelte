<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8bv8lbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8bv8lbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trash-one" {...props}></Icon>
