<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5j0rp9zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5j0rp9zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:stethoscope-alt" {...props}></Icon>
