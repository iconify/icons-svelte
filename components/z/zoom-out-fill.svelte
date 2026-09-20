<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlkrr1bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlkrr1bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:zoom-out-fill" {...props}></Icon>
