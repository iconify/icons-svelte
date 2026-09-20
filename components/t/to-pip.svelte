<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th9qdhbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th9qdhbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:to-pip" {...props}></Icon>
