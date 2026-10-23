<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4it59bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4it59bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:slice" {...props}></Icon>
