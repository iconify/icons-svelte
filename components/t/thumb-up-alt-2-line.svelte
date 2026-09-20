<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsqwvubjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsqwvubjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-up-alt-2-line" {...props}></Icon>
