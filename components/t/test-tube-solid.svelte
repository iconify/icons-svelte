<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmhvf_b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmhvf_b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:test-tube-solid" {...props}></Icon>
