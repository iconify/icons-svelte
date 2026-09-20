<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw2pvyd_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw2pvyd_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tanstack" {...props}></Icon>
