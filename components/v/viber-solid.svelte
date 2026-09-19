<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na-kpqbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="na-kpqbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:viber-solid" {...props}></Icon>
