<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_nhs_bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_nhs_bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:table-solid" {...props}></Icon>
