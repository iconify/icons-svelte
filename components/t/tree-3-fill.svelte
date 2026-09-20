<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg352rb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg352rb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-3-fill" {...props}></Icon>
