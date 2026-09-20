<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr4lprbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr4lprbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:work-from-home-user-pet-cat-bold" {...props}></Icon>
