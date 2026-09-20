<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjsr0epqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjsr0epqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:triumphal-arch-fill" {...props}></Icon>
