<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2zehzc2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2zehzc2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:warning-shield-remix" {...props}></Icon>
