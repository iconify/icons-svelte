<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u47c1vb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u47c1vb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:truck-delivery-pin" {...props}></Icon>
