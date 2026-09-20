<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o84h6-jkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o84h6-jkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:servers" {...props}></Icon>
