<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvkjf9-0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvkjf9-0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:squares-2x2-solid" {...props}></Icon>
