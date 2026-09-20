<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/ht5wlpmij.css';
import '../../css/o/ogd71bbce.css';
import '../../css/y/y02hd5l5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ht5wlpmij"/><circle class="ogd71bbce"/><circle class="y02hd5l5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:scooter" {...props}></Icon>
