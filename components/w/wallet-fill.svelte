<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubk5lxb9k.css';
import '../../css/l/l8nart8of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubk5lxb9k"/><path clip-rule="evenodd" class="l8nart8of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:wallet-fill" {...props}></Icon>
