<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suepl7i9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suepl7i9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:timer-minus-filled" {...props}></Icon>
