<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsp17zbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsp17zbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skateboarding-fill" {...props}></Icon>
