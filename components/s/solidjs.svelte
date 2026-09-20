<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ynjz1cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ynjz1cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:solidjs" {...props}></Icon>
