<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjp588bse.css';
import '../../css/y/yas-v_bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjp588bse"/><path class="yas-v_bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tennis-ball-alt-filled" {...props}></Icon>
