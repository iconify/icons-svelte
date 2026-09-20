<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhvkqfn8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhvkqfn8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sound-recognition-search-solid" {...props}></Icon>
