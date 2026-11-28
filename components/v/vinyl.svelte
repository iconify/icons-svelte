<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl083ccqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl083ccqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:vinyl" {...props}></Icon>
