<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9cagzpjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9cagzpjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wolf-solid" {...props}></Icon>
