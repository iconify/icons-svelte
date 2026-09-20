<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsjyq1ccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsjyq1ccj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-bold" {...props}></Icon>
