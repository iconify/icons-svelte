<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec2i-oxwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ec2i-oxwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:triangle-right" {...props}></Icon>
