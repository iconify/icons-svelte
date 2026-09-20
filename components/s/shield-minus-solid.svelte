<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0l3m7e7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0l3m7e7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-minus-solid" {...props}></Icon>
