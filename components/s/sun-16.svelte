<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knw8v0bgi.css';
import '../../css/f/fr9co-jbx.css';
import '../../css/c/c3eibnbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="knw8v0bgi"/><path clip-rule="evenodd" class="fr9co-jbx"/><path class="c3eibnbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sun-16" {...props}></Icon>
