<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7b8dez1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7b8dez1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-down-right-fill" {...props}></Icon>
