<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcuzocb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcuzocb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:unlock-alt" {...props}></Icon>
