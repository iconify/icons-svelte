<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orzt67brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orzt67brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:timeout" {...props}></Icon>
