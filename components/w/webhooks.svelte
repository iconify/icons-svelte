<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfn4-gb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfn4-gb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:webhooks" {...props}></Icon>
