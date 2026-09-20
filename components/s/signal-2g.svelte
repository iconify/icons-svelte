<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi71-2bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi71-2bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:signal-2g" {...props}></Icon>
