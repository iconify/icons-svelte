<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twxpq_bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="twxpq_bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:switch" {...props}></Icon>
