<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpxwfh1kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpxwfh1kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tag-chevron-fill" {...props}></Icon>
