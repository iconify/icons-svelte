<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qus4oocsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qus4oocsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-wrap-fill-round" {...props}></Icon>
