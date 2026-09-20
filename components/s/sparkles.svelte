<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egq5z7b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egq5z7b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sparkles" {...props}></Icon>
