<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox180vb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ox180vb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:xls-file" {...props}></Icon>
