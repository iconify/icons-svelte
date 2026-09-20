<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp6xi0bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp6xi0bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rubyonrails" {...props}></Icon>
