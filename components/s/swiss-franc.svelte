<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_o5d1bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_o5d1bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:swiss-franc" {...props}></Icon>
