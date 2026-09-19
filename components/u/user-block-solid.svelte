<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4m4zn7_l.css';
import '../../css/v/vawhvpbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4m4zn7_l"/><path clip-rule="evenodd" class="vawhvpbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:user-block-solid" {...props}></Icon>
