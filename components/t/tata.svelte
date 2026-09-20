<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwtj_x3al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwtj_x3al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tata" {...props}></Icon>
