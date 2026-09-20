<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytd48tbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ytd48tbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sharing-data-solid" {...props}></Icon>
