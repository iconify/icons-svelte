<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpf_jubge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpf_jubge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:volleyball" {...props}></Icon>
