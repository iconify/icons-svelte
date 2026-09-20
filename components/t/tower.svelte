<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyhn5_blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhn5_blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tower" {...props}></Icon>
