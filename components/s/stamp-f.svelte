<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-v1cdcgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="m-v1cdcgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:stamp-f" {...props}></Icon>
