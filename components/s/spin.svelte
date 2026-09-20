<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwidnkbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwidnkbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:spin" {...props}></Icon>
