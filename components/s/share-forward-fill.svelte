<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2dhhlbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2dhhlbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-forward-fill" {...props}></Icon>
