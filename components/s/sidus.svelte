<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb085db6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb085db6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sidus" {...props}></Icon>
