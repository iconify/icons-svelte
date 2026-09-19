<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c818x0b4f.css';
import '../../css/h/h8vkg4b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="c818x0b4f"/><path class="h8vkg4b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:unlock-fill" {...props}></Icon>
