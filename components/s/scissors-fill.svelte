<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehzh1igzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehzh1igzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:scissors-fill" {...props}></Icon>
