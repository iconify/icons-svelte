<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st444nbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st444nbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:table-cells" {...props}></Icon>
