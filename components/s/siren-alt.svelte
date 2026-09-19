<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn09w3stf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn09w3stf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:siren-alt" {...props}></Icon>
