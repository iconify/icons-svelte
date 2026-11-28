<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfsvxz4qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfsvxz4qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shopping-basket-solid" {...props}></Icon>
