<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0m2_d1fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0m2_d1fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sofa-fill-round" {...props}></Icon>
