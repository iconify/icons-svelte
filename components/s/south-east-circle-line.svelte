<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btoqpjbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btoqpjbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-east-circle-line" {...props}></Icon>
