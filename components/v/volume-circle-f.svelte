<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmf4wli9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="mmf4wli9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:volume-circle-f" {...props}></Icon>
