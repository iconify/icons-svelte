<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1yk2dbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1yk2dbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:watch2" {...props}></Icon>
