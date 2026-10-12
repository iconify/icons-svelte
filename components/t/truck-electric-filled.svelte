<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/now_6ismn.css';
import '../../css/q/q7s1dob3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="now_6ismn"/><path class="q7s1dob3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:truck-electric-filled" {...props}></Icon>
