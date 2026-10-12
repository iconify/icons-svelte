<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6te3llwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6te3llwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:test-tube-filled" {...props}></Icon>
