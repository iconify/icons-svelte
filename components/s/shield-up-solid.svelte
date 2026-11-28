<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk0fb3byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk0fb3byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-up-solid" {...props}></Icon>
