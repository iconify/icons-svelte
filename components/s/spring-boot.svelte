<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2-xn6r_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2-xn6r_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spring-boot" {...props}></Icon>
