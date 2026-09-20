<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tha48qd7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tha48qd7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sanitizer" {...props}></Icon>
