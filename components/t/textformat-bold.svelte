<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuqs0aczp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuqs0aczp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:textformat-bold" {...props}></Icon>
