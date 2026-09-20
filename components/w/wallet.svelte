<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3h9z2bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3h9z2bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:wallet" {...props}></Icon>
