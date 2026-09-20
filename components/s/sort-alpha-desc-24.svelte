<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu5mrjb6u.css';
import '../../css/p/prbk2rl9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu5mrjb6u"/><path clip-rule="evenodd" class="prbk2rl9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-alpha-desc-24" {...props}></Icon>
