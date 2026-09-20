<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o52-yzblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o52-yzblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:subject" {...props}></Icon>
