<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o67rcdcet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o67rcdcet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sunrise" {...props}></Icon>
