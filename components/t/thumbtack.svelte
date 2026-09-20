<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksit7p2xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ksit7p2xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:thumbtack" {...props}></Icon>
