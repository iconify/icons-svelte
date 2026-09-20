<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6e-3dwpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6e-3dwpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-commit-start-next-local" {...props}></Icon>
