<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gor4ayb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gor4ayb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:signal-full-remix" {...props}></Icon>
