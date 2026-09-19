<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s27uf9b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s27uf9b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-favorite-filled" {...props}></Icon>
