<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyzz1lqqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyzz1lqqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wgpu" {...props}></Icon>
