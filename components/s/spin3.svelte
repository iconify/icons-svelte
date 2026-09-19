<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/som_9bofx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="som_9bofx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:spin3" {...props}></Icon>
