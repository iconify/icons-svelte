<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/airnd3bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="airnd3bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:step-back-filled" {...props}></Icon>
