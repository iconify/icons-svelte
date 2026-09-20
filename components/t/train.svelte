<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjw6eqb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="fjw6eqb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:train" {...props}></Icon>
