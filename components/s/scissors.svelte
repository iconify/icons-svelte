<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w38fo_d8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="w38fo_d8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:scissors" {...props}></Icon>
