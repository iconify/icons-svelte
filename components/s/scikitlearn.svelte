<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swupuivmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swupuivmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:scikitlearn" {...props}></Icon>
