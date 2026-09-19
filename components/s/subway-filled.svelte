<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o36p4fb4z.css';
import '../../css/c/cj_6u2bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o36p4fb4z"/><path class="cj_6u2bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:subway-filled" {...props}></Icon>
