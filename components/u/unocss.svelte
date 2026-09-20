<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb1n6kb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb1n6kb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:unocss" {...props}></Icon>
