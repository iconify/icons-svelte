<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9twe9r7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9twe9r7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ticket-star-remix" {...props}></Icon>
