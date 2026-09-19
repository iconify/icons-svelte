<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsg9ci29x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsg9ci29x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tennis-ball" {...props}></Icon>
