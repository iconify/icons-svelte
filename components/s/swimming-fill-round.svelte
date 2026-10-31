<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob2rxub8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob2rxub8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:swimming-fill-round" {...props}></Icon>
