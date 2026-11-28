<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro42e1bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ro42e1bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:workflow-duotone" {...props}></Icon>
