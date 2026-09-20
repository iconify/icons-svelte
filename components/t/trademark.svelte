<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eee5vqkqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eee5vqkqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:trademark" {...props}></Icon>
