<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cydmgacai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cydmgacai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-italic" {...props}></Icon>
